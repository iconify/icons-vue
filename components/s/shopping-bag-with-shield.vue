<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vz_46dbjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="vz_46dbjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:shopping-bag-with-shield" /></template>
