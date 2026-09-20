<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lejn1miiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="lejn1miiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-scrambling-on-cliff-wearing-backpack" /></template>
