<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jbsg529cw.css';
import '../../css/s/sto-m6bio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jbsg529cw"/><path class="sto-m6bio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:month" /></template>
