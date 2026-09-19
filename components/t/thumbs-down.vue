<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zo89bj-np.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zo89bj-np"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:thumbs-down" /></template>
