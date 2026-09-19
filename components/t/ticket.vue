<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z7jwm8e_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z7jwm8e_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:ticket" /></template>
