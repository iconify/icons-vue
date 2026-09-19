<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ygdmzg_ll.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGQleDNc7g"><path clip-rule="evenodd" class="ygdmzg_ll"/></mask></defs><path mask="url(#SVGQleDNc7g)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:triangle" /></template>
