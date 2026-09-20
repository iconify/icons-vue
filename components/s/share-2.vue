<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/apws8rb2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":25};
const content = `<path class="apws8rb2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:share-2" /></template>
