<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v__xyk2aj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v__xyk2aj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:some-snapchat" /></template>
