<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b0fux7u2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b0fux7u2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:notification" /></template>
