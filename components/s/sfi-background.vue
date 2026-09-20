<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="gelp95b3o"/><path clip-rule="evenodd" class="e0thcvbss"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:sfi-background" /></template>
<style>
.e0thcvbss {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M6.976 4A2.976 2.976 0 0 0 4 6.978v10.047A2.976 2.976 0 0 0 6.976 20h10.048A2.976 2.976 0 0 0 20 17.024V6.977A2.977 2.977 0 0 0 17.023 4zm3.956 8s.017-.03 0 3.5v2.926h2.14V15.5c0-.734.004-1.428.007-2.002c.004-.83.008-1.41-.006-1.496c.507-.184 1.037-.43 1.48-.637c.64-.3 1.282-.928 1.553-1.52c.389-.849.416-1.489.11-2.525c-.269-.908-.276-1.22-.038-1.603c.078-.126.137-.196.124-.25c-.02-.087-.23-.13-.857-.298c-.556-.149-.556-.149-.655-.017c-.332.44-.35 1.256-.045 2.205c.336 1.045.238 1.82-.306 2.422c-.243.269-.72.53-1.212.666c-.489.135-1.873.136-2.424.003c-1.018-.248-1.594-.814-1.718-1.693c-.064-.453-.013-.796.226-1.522c.24-.724.26-1.4.058-1.85c-.193-.426-.288-.397-.863-.22l-.12.038l-.697.237l.173.331c.227.434.22.7-.044 1.483c-.257.764-.303 1.287-.17 1.89c.196.878.682 1.564 1.465 2.068l.098.063c.533.344.946.61 1.72.726m-.536 4.82H7.72v1.07h2.676zm5.888 0h-2.676v1.07h2.676zm-5.888-2.141H7.72v1.07h2.676zm5.888 0h-2.676v1.07h2.676zm-5.888-2.141H7.72v1.07h2.676zm5.888 0h-2.676v1.07h2.676zm-5.323-2.298C11.3 10.26 11.89 8.41 12 8c.018.05.052.175.098.342c.179.654.536 1.957.782 1.957c.027 0 1.193-.61 1.233-.646c.01-.008-.342-.686-.781-1.505L12.5 6.5h-1l-1.003 1.658L9.7 9.655l.6.29c.33.161.628.293.661.295");
}

.ft5dv1b6b {
  fill: none;
}

.gelp95b3o {
  fill: var(--svg-color--c44536, #c44536);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
