<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ojipf5b3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ojipf5b3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:some-tommelned" /></template>
