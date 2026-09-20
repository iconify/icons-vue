<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vi0lwub-e.css';
import '../../css/e/eekz3efxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vi0lwub-e"/><path class="eekz3efxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:random" /></template>
