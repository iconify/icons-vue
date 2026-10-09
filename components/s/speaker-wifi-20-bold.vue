<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nb8q1pmkh.css';
import '../../css/s/suvwyfb8m.css';
import '../../css/v/v57n--bcr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nb8q1pmkh"/><path class="suvwyfb8m"/><path class="v57n--bcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:speaker-wifi-20-bold" /></template>
