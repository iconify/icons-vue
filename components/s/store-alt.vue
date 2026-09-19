<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q680kxb5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="q680kxb5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:store-alt" /></template>
