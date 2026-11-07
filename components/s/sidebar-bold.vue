<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzmx73baa.css';
import '../../css/j/jt5nlubqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pzmx73baa"/><path clip-rule="evenodd" class="jt5nlubqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sidebar-bold" /></template>
