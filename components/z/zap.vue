<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bhm81xbjd.css';
import '../../css/h/hqfaq1dih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bhm81xbjd"/><path class="hqfaq1dih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:zap" /></template>
