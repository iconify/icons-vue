<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5qs4zbpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="b5qs4zbpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:plus-20-solid" /></template>
