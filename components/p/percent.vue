<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/guff1aclc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="guff1aclc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:percent" /></template>
