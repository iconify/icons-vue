<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kaie1r4rd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="kaie1r4rd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:uni7981-box-filled" /></template>
