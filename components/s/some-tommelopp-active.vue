<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmy9nob7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kmy9nob7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:some-tommelopp-active" /></template>
