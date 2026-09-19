<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bske83x9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="bske83x9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:outbox" /></template>
