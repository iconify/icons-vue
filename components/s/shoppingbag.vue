<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-4so2v2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1023};
const content = `<path class="x-4so2v2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:shoppingbag" /></template>
