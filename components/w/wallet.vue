<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a8egmnwzy.css';
import '../../css/c/civwcmd-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a8egmnwzy"/><path class="civwcmd-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:wallet" /></template>
