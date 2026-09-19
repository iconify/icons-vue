<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kd9xvfbsl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="kd9xvfbsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:public-address-loudspeaker" /></template>
