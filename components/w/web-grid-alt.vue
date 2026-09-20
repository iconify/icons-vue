<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h5kja2bmt.css';
import '../../css/q/qv0ny4dca.css';
import '../../css/d/dboargo5b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h5kja2bmt"/><path class="qv0ny4dca"/><path class="dboargo5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:web-grid-alt" /></template>
