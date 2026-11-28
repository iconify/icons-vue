<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vl9aqubvn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vl9aqubvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:sofa-heart" /></template>
