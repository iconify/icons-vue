<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ls90sccbc.css';
import '../../css/z/z72p7wbvz.css';
import '../../css/w/w6tbsj31t.css';
import '../../css/v/vj7jxi4uw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ls90sccbc wm-k"/><path class="wm-k z72p7wbvz"/><path class="w6tbsj31t wm-a"/><path class="vj7jxi4uw wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:smartphone" /></template>
