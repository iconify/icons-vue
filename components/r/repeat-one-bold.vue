<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ashhbpb5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ashhbpb5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:repeat-one-bold" /></template>
