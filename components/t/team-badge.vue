<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eya5gc0ce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:team-badge" /></template>
<style>
.eya5gc0ce {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m19.779 4.804l-7.5-3Q12.144 1.75 12 1.75t-.279.054l-7.5 3q-.104.041-.191.112q-.088.07-.151.164q-.063.093-.096.2t-.033.22V11q0 7.214 7.915 11.171q.078.039.163.059t.172.02t.172-.02t.163-.059Q20.25 18.214 20.25 11V5.5q0-.112-.033-.22q-.033-.107-.096-.2t-.151-.164q-.087-.071-.191-.112m-6.583 3.917l.123.307q.189.472.697.472h.234q.845.002 1.141.791t-.337 1.345l-.334.293q-.363.317-.225.779l.098.326q.247.822-.443 1.332q-.689.51-1.402.034l-.332-.221q-.416-.277-.832 0l-.332.221q-.713.476-1.402-.034q-.69-.51-.443-1.331l.098-.327q.138-.462-.225-.78l-.333-.29q-.634-.558-.338-1.347T9.748 9.5h.236q.508 0 .697-.472l.123-.307q.325-.809 1.196-.809t1.196.808z");
}

</style>
