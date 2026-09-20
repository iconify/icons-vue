<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pqg1arbtz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pqg1arbtz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:terminal-alt-fill" /></template>
