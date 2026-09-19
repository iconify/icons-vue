<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bdz9vxb_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":472};
const content = `<path class="bdz9vxb_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:sound-plus" /></template>
