<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i05wloydx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i05wloydx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:shopping-bag-sharp-fill" /></template>
