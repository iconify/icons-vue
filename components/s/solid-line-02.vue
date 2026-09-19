<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/grbs_c4kf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="grbs_c4kf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:solid-line-02" /></template>
