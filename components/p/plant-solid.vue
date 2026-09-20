<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g8nx62r-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="g8nx62r-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:plant-solid" /></template>
