<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1vnqtbdy.css';
import '../../css/j/jdmutcjtc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l1vnqtbdy"/><path class="jdmutcjtc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:puck-filled" /></template>
