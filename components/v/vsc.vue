<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzyozrbpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pzyozrbpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:vsc" /></template>
