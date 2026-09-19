<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/efr8e-b8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="efr8e-b8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:share-rounded" /></template>
