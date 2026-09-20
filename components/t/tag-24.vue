<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7gi09b7p.css';
import '../../css/z/zpma4hb3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u7gi09b7p"/><path class="zpma4hb3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:tag-24" /></template>
