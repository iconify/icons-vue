<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tqzu5893t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="tqzu5893t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:vending-machine" /></template>
