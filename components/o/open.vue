<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dp2-434cc.css';
import '../../css/m/mzibl9poh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dp2-434cc"/><path class="mzibl9poh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:open" /></template>
