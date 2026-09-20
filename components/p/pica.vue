<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ypjo1vb5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:pica" /></template>
<style>
.ypjo1vb5g {
  fill: var(--svg-color--282828, #282828);
  fill-rule: evenodd;
  d: path("M10.714 3H3v18h7.714v-6.454c.964.43 2.057.668 3.214.668c3.91 0 7.072-2.732 7.072-6.107S17.837 3 13.929 3c-1.158 0-2.25.238-3.215.669zm3.214 11.572a7.2 7.2 0 0 1-3.214-.733V4.376a7.3 7.3 0 0 1 3.214-.733c3.55 0 6.43 2.443 6.43 5.464s-2.88 5.465-6.43 5.465M7.5 9.107c0 1.787 1.01 3.375 2.572 4.372V4.736C8.509 5.732 7.5 7.32 7.5 9.107m-.643 0c0-2.14 1.28-4.03 3.215-5.117v-.347h-6.43v16.714h6.43v-6.133c-1.936-1.092-3.215-2.976-3.215-5.117M21 15.214V21c-1.774 0-3.214-1.292-3.214-2.893s1.44-2.893 3.214-2.893");
}

</style>
