<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cwu44rb_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cwu44rb_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:web-grid" /></template>
