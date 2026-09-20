<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f7ejmibhb.css';
import '../../css/z/z6i6gousf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f7ejmibhb"/><path class="z6i6gousf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:video" /></template>
