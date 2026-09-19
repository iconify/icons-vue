<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7arko27i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="j7arko27i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:pin-slash-fill" /></template>
