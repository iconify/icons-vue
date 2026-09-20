<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n5mqmsbgz.css';
import '../../css/j/juxduqi5b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n5mqmsbgz"/><path clip-rule="evenodd" class="juxduqi5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:view-compact-fill" /></template>
