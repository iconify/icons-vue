<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fx5nclbzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fx5nclbzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:remove-favorite-highlight-solid" /></template>
