<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/osmazeb7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="osmazeb7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:mouse-sharp-fill" /></template>
