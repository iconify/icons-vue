<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qr0hxdh-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qr0hxdh-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:mouse-fill" /></template>
