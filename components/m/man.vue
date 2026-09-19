<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/skhce2wwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":512};
const content = `<path class="skhce2wwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:man" /></template>
