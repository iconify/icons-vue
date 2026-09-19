<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qhpv7xt7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="qhpv7xt7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:mug" /></template>
