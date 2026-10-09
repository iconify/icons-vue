<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fbx5zccce.css';
import '../../css/h/ht2w2gbct.css';
import '../../css/i/ip_kbyb2f.css';
import '../../css/i/iqyfmrbeb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fbx5zccce"/><path class="ht2w2gbct"/><path class="ip_kbyb2f"/><path class="iqyfmrbeb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:mvhr-20" /></template>
