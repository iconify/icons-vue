<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/apatysb6u.css';
import '../../css/s/sv53ehbxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="apatysb6u"/><path class="sv53ehbxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:phb" /></template>
