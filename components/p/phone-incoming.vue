<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cw6fjgo-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cw6fjgo-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:phone-incoming" /></template>
