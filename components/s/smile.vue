<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wqbkv8u2i.css';
import '../../css/i/ifg4aac8u.css';
import '../../css/z/ze9xnfzdp.css';
import '../../css/q/q26grc28u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wqbkv8u2i"/><path class="ifg4aac8u"/><circle class="ze9xnfzdp"/><circle class="q26grc28u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:smile" /></template>
