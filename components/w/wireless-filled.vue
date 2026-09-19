<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gbwx0nb3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="gbwx0nb3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:wireless-filled" /></template>
