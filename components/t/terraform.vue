<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lwwg9_gwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lwwg9_gwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:terraform" /></template>
