<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jyt4rsbar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jyt4rsbar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:phone-x" /></template>
