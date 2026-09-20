<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gvxwz-brr.css';
import '../../css/z/zpzbcrshu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gvxwz-brr"/><path class="zpzbcrshu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:rope-fence" /></template>
