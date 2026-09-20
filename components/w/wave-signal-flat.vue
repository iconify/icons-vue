<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx3_xqbix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jx3_xqbix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp-color:wave-signal-flat" /></template>
