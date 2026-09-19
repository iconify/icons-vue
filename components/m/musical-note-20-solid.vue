<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pbtrplbda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="pbtrplbda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:musical-note-20-solid" /></template>
