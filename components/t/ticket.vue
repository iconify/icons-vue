<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kc01oya5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":768};
const content = `<path class="kc01oya5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:ticket" /></template>
