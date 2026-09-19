<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uk4jgzb_e.css';
import '../../css/h/hdloyab2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uk4jgzb_e"/><path class="hdloyab2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:symlink-outlined" /></template>
