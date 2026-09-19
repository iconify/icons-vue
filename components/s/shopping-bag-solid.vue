<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_fo7cb7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a_fo7cb7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:shopping-bag-solid" /></template>
