<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/offmweb-q.css';
import '../../css/g/gotjsow0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="offmweb-q"/><path class="gotjsow0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:wallet-light" /></template>
