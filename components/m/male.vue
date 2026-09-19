<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kfn9sqbvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":432};
const content = `<path class="kfn9sqbvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:male" /></template>
