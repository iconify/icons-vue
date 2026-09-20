<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hlkrr1bkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hlkrr1bkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:zoom-out-fill" /></template>
