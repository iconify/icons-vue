<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pf6w5_bfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":896};
const content = `<path class="pf6w5_bfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:osclass" /></template>
