<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhk-zbc0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yhk-zbc0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:workspace-unknown" /></template>
