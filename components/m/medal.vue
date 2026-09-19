<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1kq5gpqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="l1kq5gpqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:medal" /></template>
