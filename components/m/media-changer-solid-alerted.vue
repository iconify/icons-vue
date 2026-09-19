<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ij_mazs6p.css';
import '../../css/u/uaycyrbmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="ij_mazs6p"/><path class="uaycyrbmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:media-changer-solid-alerted" /></template>
