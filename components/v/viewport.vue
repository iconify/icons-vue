<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/avxsmbc0e.css';
import '../../css/t/tyy5pn3_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="avxsmbc0e"/><path class="tyy5pn3_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:viewport" /></template>
