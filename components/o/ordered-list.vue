<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vm3m3rbar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vm3m3rbar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:ordered-list" /></template>
