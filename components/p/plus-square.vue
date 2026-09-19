<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t71jnss5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="t71jnss5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:plus-square" /></template>
