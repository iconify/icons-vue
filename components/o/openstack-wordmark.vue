<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ae8cvcbjo.css';
import '../../css/z/zdxltopzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ae8cvcbjo"/><path class="zdxltopzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:openstack-wordmark" /></template>
