<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/paurdn42f.css';
import '../../css/w/ws0xuezat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="paurdn42f"/><path class="ws0xuezat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:system-group" /></template>
