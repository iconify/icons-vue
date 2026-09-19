<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p79y4pbes.css';
import '../../css/l/l7avsacre.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="p79y4pbes"/><circle class="l7avsacre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:notification-new" /></template>
