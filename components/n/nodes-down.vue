<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_4x7bc7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="p_4x7bc7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:nodes-down" /></template>
