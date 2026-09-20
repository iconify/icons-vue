<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkuff2bgq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dkuff2bgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:play-btn-light" /></template>
