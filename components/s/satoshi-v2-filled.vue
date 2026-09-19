<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o6ltt5byn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o6ltt5byn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:satoshi-v2-filled" /></template>
