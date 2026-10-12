<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ui5tlxbrr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ui5tlxbrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:text-heading-five" /></template>
