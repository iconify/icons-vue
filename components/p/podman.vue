<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oghq11qud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oghq11qud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:podman" /></template>
