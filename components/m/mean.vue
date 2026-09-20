<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGNwAMZdhU)" clip-rule="evenodd" class="t-y9a_6va"/><defs><linearGradient id="SVGNwAMZdhU" x1="12" x2="12" y1="3.563" y2="20.437" gradientUnits="userSpaceOnUse"><stop class="ih7cttb9k"/><stop offset="1" class="gav1c7bmd"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:mean" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gav1c7bmd {
  stop-color: var(--svg-color--b8091c, #b8091c);
}

.ih7cttb9k {
  stop-color: var(--svg-color--f40315, #f40315);
}

.t-y9a_6va {
  fill-rule: evenodd;
  d: path("M20.438 3L12 5.25L3.563 3C3.563 4.901 3 6.937 3 6.937l3.589 9.833l5.41 4.23l5.412-4.23L21 6.937c-.056 0-.562-2.036-.562-3.937M12 6.937L5.25 5.25c0 1.66-.371 2.12-.371 2.12l3.183 8.286l1.688 1.406L6.937 7.5l3.375 1.125l1.125 8.719L12 18.75l.563-1.406l1.124-8.719L17.063 7.5l-2.813 9.563l1.687-1.407l3.184-8.285s-.371-.71-.371-2.121z");
}

</style>
