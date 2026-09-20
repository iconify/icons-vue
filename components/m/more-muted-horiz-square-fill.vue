<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ae1arr37i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ae1arr37i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:more-muted-horiz-square-fill" /></template>
