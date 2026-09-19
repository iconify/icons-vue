<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pgso-g05s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pgso-g05s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:wechat" /></template>
