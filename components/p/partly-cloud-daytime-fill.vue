<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iuo2kw2qw.css';
import '../../css/n/n54i3ab4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iuo2kw2qw"/><path class="n54i3ab4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:partly-cloud-daytime-fill" /></template>
