<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zy7l49bbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zy7l49bbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:shield-plus" /></template>
