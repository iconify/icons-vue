<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o27r778ow.css';
import '../../css/i/iq9a7xo1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="o27r778ow"/><path class="iq9a7xo1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:out" /></template>
