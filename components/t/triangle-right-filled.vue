<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n3ptqkb9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="n3ptqkb9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:triangle-right-filled" /></template>
