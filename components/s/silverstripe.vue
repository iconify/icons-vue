<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t3t2e4m8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1026,"height":1022};
const content = `<path class="t3t2e4m8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:silverstripe" /></template>
