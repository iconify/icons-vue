<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp0cwnbgx.css';
import '../../css/y/y4fef2bqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gp0cwnbgx"/><path class="y4fef2bqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sofa-bold-duotone" /></template>
