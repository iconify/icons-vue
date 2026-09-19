<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k3nbakb9b.css';
import '../../css/l/lsid_0bha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="k3nbakb9b"/><path class="lsid_0bha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="geo:turf-size" /></template>
