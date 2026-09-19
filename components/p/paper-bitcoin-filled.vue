<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a9-ahhtng.css';
import '../../css/j/jrhlkt36v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a9-ahhtng"/><path clip-rule="evenodd" class="jrhlkt36v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:paper-bitcoin-filled" /></template>
