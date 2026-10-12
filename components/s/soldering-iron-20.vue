<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/twyecdg0k.css';
import '../../css/t/tzg0a7gil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="twyecdg0k"/><path class="tzg0a7gil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:soldering-iron-20" /></template>
