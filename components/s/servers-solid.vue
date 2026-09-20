<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bpecr9k8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="bpecr9k8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:servers-solid" /></template>
