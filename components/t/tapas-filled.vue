<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n3mo1ml7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n3mo1ml7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:tapas-filled" /></template>
