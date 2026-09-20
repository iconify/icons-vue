<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bb66-30dn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bb66-30dn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:square-arrows-up-filled" /></template>
