<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vyf4oybuy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vyf4oybuy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:triangle-plus-2" /></template>
