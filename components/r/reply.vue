<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4iyz2z_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="v4iyz2z_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:reply" /></template>
