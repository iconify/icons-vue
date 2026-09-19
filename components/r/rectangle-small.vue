<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a9fio_3zp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a9fio_3zp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:rectangle-small" /></template>
