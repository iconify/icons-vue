<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qtm430bpk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="qtm430bpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:person-plus" /></template>
