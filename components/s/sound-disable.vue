<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pfg596bgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pfg596bgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:sound-disable" /></template>
