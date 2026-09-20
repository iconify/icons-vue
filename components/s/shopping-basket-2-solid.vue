<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/et3kqvbaj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="et3kqvbaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:shopping-basket-2-solid" /></template>
