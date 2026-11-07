<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n9y477w0i.css';
import '../../css/s/swt0kss-n.css';
import '../../css/u/u32rdbbja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="n9y477w0i"/><path class="swt0kss-n"/><path class="u32rdbbja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rounded-magnifier-slash-bold-duotone" /></template>
