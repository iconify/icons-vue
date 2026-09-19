<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/chuc7emeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="chuc7emeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:user-expert" /></template>
