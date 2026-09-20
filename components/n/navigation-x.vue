<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-i0iu56p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v-i0iu56p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:navigation-x" /></template>
