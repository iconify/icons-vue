<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a-fsf2rdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a-fsf2rdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-align-offset-bottom-fill" /></template>
