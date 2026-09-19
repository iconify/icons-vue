<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bv-xx4z6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bv-xx4z6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:stripe" /></template>
