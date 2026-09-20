<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yrypl5btf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="yrypl5btf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-spiking-volleyball" /></template>
