<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ud_9sccoj.css';
import '../../css/c/c5p-nqbdf.css';
import '../../css/w/wc2m4bc5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ud_9sccoj"/><path class="c5p-nqbdf"/><path class="wc2m4bc5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:text-field-focus-outline" /></template>
