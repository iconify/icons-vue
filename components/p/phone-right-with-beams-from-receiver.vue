<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pqljvpq9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="pqljvpq9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:phone-right-with-beams-from-receiver" /></template>
