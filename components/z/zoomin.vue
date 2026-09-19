<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwys74b8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":717,"height":766};
const content = `<path class="mwys74b8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:zoomin" /></template>
