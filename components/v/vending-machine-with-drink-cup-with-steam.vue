<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lb7byjbii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="lb7byjbii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:vending-machine-with-drink-cup-with-steam" /></template>
